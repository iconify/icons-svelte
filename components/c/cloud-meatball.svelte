<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7706u1il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q7706u1il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud-meatball" {...props}></Icon>
