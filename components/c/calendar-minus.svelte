<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab1rb1ihn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ab1rb1ihn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:calendar-minus" {...props}></Icon>
