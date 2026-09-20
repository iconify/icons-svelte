<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au9hlnb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="au9hlnb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:minus-outline" {...props}></Icon>
