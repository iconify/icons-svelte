<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mafp-cc6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mafp-cc6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:airplane-mode" {...props}></Icon>
