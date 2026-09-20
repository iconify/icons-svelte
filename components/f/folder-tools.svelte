<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5fxn4-5j.css';
import '../../css/r/ryg6a4aqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i5fxn4-5j"/><path class="ryg6a4aqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-tools" {...props}></Icon>
