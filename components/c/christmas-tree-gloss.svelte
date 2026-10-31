<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iythkqbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iythkqbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:christmas-tree-gloss" {...props}></Icon>
