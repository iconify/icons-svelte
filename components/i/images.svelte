<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq9tasb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zq9tasb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:images" {...props}></Icon>
