<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz-xmkcja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="oz-xmkcja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:arrowup" {...props}></Icon>
