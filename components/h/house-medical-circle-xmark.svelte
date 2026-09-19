<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-c44pbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="h-c44pbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-medical-circle-xmark" {...props}></Icon>
