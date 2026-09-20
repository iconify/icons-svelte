<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj9s6j9ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aj9s6j9ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-repo-16" {...props}></Icon>
