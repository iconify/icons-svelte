<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e206mkber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e206mkber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:java-exception" {...props}></Icon>
