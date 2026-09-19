<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkbm2ibaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="kkbm2ibaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:accusoft" {...props}></Icon>
