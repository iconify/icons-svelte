<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um9_oznhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="um9_oznhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:list" {...props}></Icon>
