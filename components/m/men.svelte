<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf_1rfblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf_1rfblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:men" {...props}></Icon>
