<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfkgk1l5g.css';
import '../../css/u/ugxf3ybrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xfkgk1l5g"/><path class="ugxf3ybrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:anchor" {...props}></Icon>
