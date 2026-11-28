<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laisf1b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laisf1b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fox" {...props}></Icon>
