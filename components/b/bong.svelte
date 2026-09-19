<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j25ju4bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="j25ju4bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bong" {...props}></Icon>
