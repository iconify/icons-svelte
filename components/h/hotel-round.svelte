<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpm7dvn9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpm7dvn9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hotel-round" {...props}></Icon>
