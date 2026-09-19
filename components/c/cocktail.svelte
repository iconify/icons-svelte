<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij-b_giyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij-b_giyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cocktail" {...props}></Icon>
