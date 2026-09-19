<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqtd8hbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="uqtd8hbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chess-king" {...props}></Icon>
