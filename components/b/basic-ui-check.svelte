<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f97xkqb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f97xkqb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-check" {...props}></Icon>
