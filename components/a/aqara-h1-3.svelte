<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v214gw1op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v214gw1op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-h1-3" {...props}></Icon>
