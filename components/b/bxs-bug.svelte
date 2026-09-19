<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqbp7ccct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqbp7ccct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bug" {...props}></Icon>
