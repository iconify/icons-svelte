<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2d838bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2d838bfi primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:filter-duotone" {...props}></Icon>
