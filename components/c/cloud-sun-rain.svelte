<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1puo02_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="p1puo02_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cloud-sun-rain" {...props}></Icon>
