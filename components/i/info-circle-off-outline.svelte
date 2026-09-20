<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkzi7gbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkzi7gbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:info-circle-off-outline" {...props}></Icon>
