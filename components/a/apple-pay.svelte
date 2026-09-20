<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd9e1pbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pd9e1pbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:apple-pay" {...props}></Icon>
