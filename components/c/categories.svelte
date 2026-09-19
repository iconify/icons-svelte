<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krvn_ccod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="krvn_ccod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:categories" {...props}></Icon>
