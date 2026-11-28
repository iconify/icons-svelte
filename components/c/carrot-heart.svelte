<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0mm06vly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0mm06vly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:carrot-heart" {...props}></Icon>
