<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovb1mgbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ovb1mgbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cart-fill-badge-plus" {...props}></Icon>
