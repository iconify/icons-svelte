<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w336_2pbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w336_2pbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:grid-big-round" {...props}></Icon>
