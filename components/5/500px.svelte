<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p02trow8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":24};
const content = `<path class="p02trow8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:500px" {...props}></Icon>
