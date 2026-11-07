<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpv5ewbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpv5ewbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-turn-off-outline" {...props}></Icon>
