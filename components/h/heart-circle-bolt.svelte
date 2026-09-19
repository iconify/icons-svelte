<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu8eqhbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pu8eqhbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:heart-circle-bolt" {...props}></Icon>
