<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfnkfhbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfnkfhbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:closed-captioning" {...props}></Icon>
