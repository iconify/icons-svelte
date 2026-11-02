<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwsekofag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwsekofag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:between-vertical-end-fill" {...props}></Icon>
