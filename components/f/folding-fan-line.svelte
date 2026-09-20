<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsut6wb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsut6wb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folding-fan-line" {...props}></Icon>
