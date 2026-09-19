<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6zuvtb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m6zuvtb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:diff-modified" {...props}></Icon>
