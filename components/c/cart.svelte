<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzid2lihz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rzid2lihz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cart" {...props}></Icon>
