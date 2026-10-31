<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uctb9sbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uctb9sbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:phone-bulk-round" {...props}></Icon>
