<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1d3vglmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1d3vglmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plane-bold" {...props}></Icon>
