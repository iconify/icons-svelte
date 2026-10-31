<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir73vwbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir73vwbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:quotation-mark" {...props}></Icon>
