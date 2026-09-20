<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h05putmmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h05putmmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:book" {...props}></Icon>
