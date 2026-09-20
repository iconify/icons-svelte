<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxrr_ccra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxrr_ccra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-exit" {...props}></Icon>
