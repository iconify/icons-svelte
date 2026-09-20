<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d91b1m4xa.css';
import '../../css/d/deymd5jrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d91b1m4xa"/><path class="deymd5jrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:external-link-16" {...props}></Icon>
