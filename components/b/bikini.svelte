<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_5pycbka.css';
import '../../css/b/bjttmb9ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="h_5pycbka"/><path class="bjttmb9ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:bikini" {...props}></Icon>
