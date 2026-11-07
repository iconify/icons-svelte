<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7_a60-yr.css';
import '../../css/t/twmo39osj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7_a60-yr"/><path class="twmo39osj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbon-star-bold-duotone" {...props}></Icon>
