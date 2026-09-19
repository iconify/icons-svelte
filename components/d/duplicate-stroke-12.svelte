<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikcfh6blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ikcfh6blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:duplicate-stroke-12" {...props}></Icon>
