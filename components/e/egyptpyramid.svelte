<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_zou2-zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":640};
const content = `<path class="e_zou2-zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:egyptpyramid" {...props}></Icon>
