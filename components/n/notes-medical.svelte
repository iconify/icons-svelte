<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqqpjxh5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sqqpjxh5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:notes-medical" {...props}></Icon>
