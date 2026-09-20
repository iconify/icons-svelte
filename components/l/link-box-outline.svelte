<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpsu0p27p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpsu0p27p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-box-outline" {...props}></Icon>
