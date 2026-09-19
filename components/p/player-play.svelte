<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0agrplwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0agrplwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-play" {...props}></Icon>
