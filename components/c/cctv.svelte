<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq3_rzi9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq3_rzi9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cctv" {...props}></Icon>
