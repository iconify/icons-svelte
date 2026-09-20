<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajs7jibwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ajs7jibwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:caret-right" {...props}></Icon>
