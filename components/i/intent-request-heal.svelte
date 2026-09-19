<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znaj4nbie.css';
import '../../css/u/uc_6-wbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="znaj4nbie"/><path class="uc_6-wbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:intent-request-heal" {...props}></Icon>
