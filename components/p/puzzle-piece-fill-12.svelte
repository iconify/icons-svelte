<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvedctbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gvedctbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:puzzle-piece-fill-12" {...props}></Icon>
