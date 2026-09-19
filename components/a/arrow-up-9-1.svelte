<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxh1f2bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="uxh1f2bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-up-9-1" {...props}></Icon>
