<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcxj3j5_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wcxj3j5_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:eye-o" {...props}></Icon>
