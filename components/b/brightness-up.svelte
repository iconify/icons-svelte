<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggrkcob9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ggrkcob9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:brightness-up" {...props}></Icon>
