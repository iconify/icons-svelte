<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgw_fbc9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgw_fbc9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-left-rhombus-filled" {...props}></Icon>
