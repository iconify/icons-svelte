<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbdu-tbiz.css';
import '../../css/v/vtxmsw_ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="xbdu-tbiz"/><path class="vtxmsw_ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:animation-line" {...props}></Icon>
