<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g05kqyb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g05kqyb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-question" {...props}></Icon>
