<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o02-1jb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o02-1jb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:exit" {...props}></Icon>
