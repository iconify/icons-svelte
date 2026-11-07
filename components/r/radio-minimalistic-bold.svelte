<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4xjtxb3p.css';
import '../../css/u/u27cghbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4xjtxb3p"/><path clip-rule="evenodd" class="u27cghbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radio-minimalistic-bold" {...props}></Icon>
