<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_ixp2b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o_ixp2b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:image-rotate-left" {...props}></Icon>
