<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucd-8ebmt.css';
import '../../css/d/d3c-6wbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ucd-8ebmt"/><path class="d3c-6wbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:info" {...props}></Icon>
