<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl7ngiv_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl7ngiv_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:enter-light" {...props}></Icon>
