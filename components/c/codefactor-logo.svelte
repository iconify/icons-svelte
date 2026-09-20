<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfr_u48ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfr_u48ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:codefactor-logo" {...props}></Icon>
