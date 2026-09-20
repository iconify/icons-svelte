<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1zld5b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":208};
const content = `<path class="j1zld5b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:github-copilot-dark" {...props}></Icon>
