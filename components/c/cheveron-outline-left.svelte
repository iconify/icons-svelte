<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um-ib7b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="um-ib7b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:cheveron-outline-left" {...props}></Icon>
