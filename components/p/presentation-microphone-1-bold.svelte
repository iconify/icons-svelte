<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o00euybwi.css';
import '../../css/t/togjpqbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o00euybwi"/><path class="togjpqbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:presentation-microphone-1-bold" {...props}></Icon>
