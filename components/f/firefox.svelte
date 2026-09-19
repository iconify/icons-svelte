<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiokicbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":764};
const content = `<path class="eiokicbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:firefox" {...props}></Icon>
