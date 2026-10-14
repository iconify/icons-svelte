<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cled29wwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cled29wwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:graph-bar-vertical-16" {...props}></Icon>
