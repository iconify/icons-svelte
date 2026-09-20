<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fudqfvb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fudqfvb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:home" {...props}></Icon>
