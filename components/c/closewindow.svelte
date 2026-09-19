<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv23k6bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="cv23k6bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:closewindow" {...props}></Icon>
