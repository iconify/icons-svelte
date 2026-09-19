<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tatr91rod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tatr91rod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:panels-stroke-12" {...props}></Icon>
