<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4czoneoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q4czoneoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bcc" {...props}></Icon>
