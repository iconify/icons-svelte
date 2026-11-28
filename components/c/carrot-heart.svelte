<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1z-hl5ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1z-hl5ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:carrot-heart" {...props}></Icon>
