<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc5wzqbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc5wzqbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pin-2-alt-bold" {...props}></Icon>
