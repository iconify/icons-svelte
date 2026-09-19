<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hszbwt4ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hszbwt4ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:dismiss" {...props}></Icon>
