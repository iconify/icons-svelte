<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxjzmobsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxjzmobsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:land-plots" {...props}></Icon>
