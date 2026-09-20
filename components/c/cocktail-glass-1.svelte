<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkow5mkrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkow5mkrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cocktail-glass-1" {...props}></Icon>
