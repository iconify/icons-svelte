<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfry1kbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfry1kbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:garage-check" {...props}></Icon>
