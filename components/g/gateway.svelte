<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_-7mtb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_-7mtb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gateway" {...props}></Icon>
