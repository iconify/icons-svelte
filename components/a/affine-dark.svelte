<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za3etc0cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="za3etc0cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:affine-dark" {...props}></Icon>
