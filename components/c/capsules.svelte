<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkq99-j3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="rkq99-j3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:capsules" {...props}></Icon>
