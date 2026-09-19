<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd0elh16c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="pd0elh16c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:photo-film" {...props}></Icon>
