<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i65-tqbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i65-tqbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cocktail-solid" {...props}></Icon>
