<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r58i4harq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r58i4harq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ring-doorbell-pro" {...props}></Icon>
