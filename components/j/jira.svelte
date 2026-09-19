<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5u6vqnyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j5u6vqnyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:jira" {...props}></Icon>
