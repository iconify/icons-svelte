<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f10ihlbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f10ihlbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:currency" {...props}></Icon>
