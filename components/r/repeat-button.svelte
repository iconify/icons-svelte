<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3nheebop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="x3nheebop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:repeat-button" {...props}></Icon>
