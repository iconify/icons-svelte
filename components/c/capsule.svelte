<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf3ch8pgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf3ch8pgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:capsule" {...props}></Icon>
