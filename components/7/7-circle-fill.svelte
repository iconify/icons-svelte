<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e28aaibcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e28aaibcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:7-circle-fill" {...props}></Icon>
