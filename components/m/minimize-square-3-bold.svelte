<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivgsmkbsz.css';
import '../../css/u/uto2arb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivgsmkbsz"/><path clip-rule="evenodd" class="uto2arb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-square-3-bold" {...props}></Icon>
