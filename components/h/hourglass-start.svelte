<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6l6uacfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="p6l6uacfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hourglass-start" {...props}></Icon>
