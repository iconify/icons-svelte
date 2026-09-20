<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w16t2pppu.css';
import '../../css/q/q9-pcgbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w16t2pppu"/><path class="q9-pcgbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:home" {...props}></Icon>
