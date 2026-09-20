<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pat2y4biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pat2y4biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:home-thatched" {...props}></Icon>
