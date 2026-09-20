<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx7o6jbbt.css';
import '../../css/k/kzp9xht2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cx7o6jbbt"/><path class="kzp9xht2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-desert-donut" {...props}></Icon>
