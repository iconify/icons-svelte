<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4bv7_8rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u4bv7_8rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:radio" {...props}></Icon>
