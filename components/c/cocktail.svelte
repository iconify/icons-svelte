<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh-3_uvfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh-3_uvfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:cocktail" {...props}></Icon>
