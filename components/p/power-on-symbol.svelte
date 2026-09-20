<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq6rqbp0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hq6rqbp0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:power-on-symbol" {...props}></Icon>
