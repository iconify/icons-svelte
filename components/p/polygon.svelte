<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr_kw94ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zr_kw94ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:polygon" {...props}></Icon>
