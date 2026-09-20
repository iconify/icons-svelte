<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2hs_cbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2hs_cbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:phone-missed" {...props}></Icon>
