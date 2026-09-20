<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg5mlp8ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg5mlp8ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrows-contract-expressive" {...props}></Icon>
