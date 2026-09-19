<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv6irtb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv6irtb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-3-square" {...props}></Icon>
