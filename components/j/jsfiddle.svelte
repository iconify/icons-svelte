<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ned736b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ned736b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:jsfiddle" {...props}></Icon>
