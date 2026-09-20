<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dluyn9c8v.css';
import '../../css/g/gj051ober.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dluyn9c8v"/><path class="gj051ober"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-bag" {...props}></Icon>
