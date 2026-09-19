<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6_fg-lkg.css';
import '../../css/i/i9urgub_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6_fg-lkg"/><path class="i9urgub_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-right-stroke-square-filled" {...props}></Icon>
