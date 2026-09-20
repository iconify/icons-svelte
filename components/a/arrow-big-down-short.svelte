<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1-d3eqbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1-d3eqbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-down-short" {...props}></Icon>
