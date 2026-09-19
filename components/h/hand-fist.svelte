<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r708_dubz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="r708_dubz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-fist" {...props}></Icon>
