<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sot2k_elk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sot2k_elk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grill-off" {...props}></Icon>
