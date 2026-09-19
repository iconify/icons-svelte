<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf38fyb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="tf38fyb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:comments-dollar" {...props}></Icon>
