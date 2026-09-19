<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mruly6l5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mruly6l5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:font" {...props}></Icon>
