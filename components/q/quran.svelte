<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5vo_hbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="h5vo_hbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:quran" {...props}></Icon>
