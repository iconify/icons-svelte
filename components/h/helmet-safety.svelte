<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp0ly3b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="fp0ly3b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:helmet-safety" {...props}></Icon>
