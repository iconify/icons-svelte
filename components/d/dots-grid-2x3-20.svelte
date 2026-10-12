<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2dwvmnwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f2dwvmnwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:dots-grid-2x3-20" {...props}></Icon>
