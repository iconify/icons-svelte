<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z90mb8szc.css';
import '../../css/a/a6h6rcbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z90mb8szc"/><path class="a6h6rcbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bathtub-20" {...props}></Icon>
