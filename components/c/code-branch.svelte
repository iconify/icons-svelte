<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8nj21w8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="c8nj21w8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:code-branch" {...props}></Icon>
