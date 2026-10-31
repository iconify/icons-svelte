<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwupfyc_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwupfyc_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-u-turn-right-up-bulk-round" {...props}></Icon>
