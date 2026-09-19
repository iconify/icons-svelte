<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8wusz0vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i8wusz0vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bos" {...props}></Icon>
