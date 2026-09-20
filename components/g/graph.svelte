<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo6ozabgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mo6ozabgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:graph" {...props}></Icon>
