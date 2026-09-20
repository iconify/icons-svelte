<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-3-5ybig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a-3-5ybig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:people" {...props}></Icon>
