<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejytsk_lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejytsk_lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-end-01" {...props}></Icon>
