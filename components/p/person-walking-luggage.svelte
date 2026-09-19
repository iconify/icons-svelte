<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2uf_k-ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="r2uf_k-ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-walking-luggage" {...props}></Icon>
