<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucgsi_b-h.css';
import '../../css/l/l35tfkbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ucgsi_b-h"/><path class="l35tfkbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightbulb-minimalistic-bold" {...props}></Icon>
