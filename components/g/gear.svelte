<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebd54rbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ebd54rbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:gear" {...props}></Icon>
