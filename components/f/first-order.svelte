<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an3sm_xkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="an3sm_xkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:first-order" {...props}></Icon>
