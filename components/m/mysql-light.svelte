<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e02a5kbah.css';
import '../../css/n/n5nnvotfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":252};
const content = `<path class="e02a5kbah"/><path class="n5nnvotfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mysql-light" {...props}></Icon>
