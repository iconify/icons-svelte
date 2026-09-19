<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6ingvywc.css';
import '../../css/n/n6_fg-lkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6ingvywc"/><path class="n6_fg-lkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-right-stroke-circle-filled" {...props}></Icon>
