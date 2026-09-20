<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_dr7acpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_dr7acpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-up-bold" {...props}></Icon>
