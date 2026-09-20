<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxku6lahb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qxku6lahb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-left-16" {...props}></Icon>
