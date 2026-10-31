<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlhn8ybms.css';
import '../../css/k/k1cse-ckm.css';
import '../../css/i/ik5eqpb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="vlhn8ybms"/><path class="k1cse-ckm"/><path class="ik5eqpb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:cuba" {...props}></Icon>
