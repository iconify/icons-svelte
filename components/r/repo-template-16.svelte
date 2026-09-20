<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8f9qnbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i8f9qnbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-template-16" {...props}></Icon>
