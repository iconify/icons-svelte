<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7-ewwg-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u7-ewwg-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-judgements" {...props}></Icon>
