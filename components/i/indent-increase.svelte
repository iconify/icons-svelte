<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-cmdre9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z-cmdre9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:indent-increase" {...props}></Icon>
