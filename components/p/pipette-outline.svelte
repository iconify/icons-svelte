<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x12s0fb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x12s0fb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pipette-outline" {...props}></Icon>
