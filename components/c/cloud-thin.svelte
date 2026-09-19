<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2uho8ifp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2uho8ifp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-thin" {...props}></Icon>
