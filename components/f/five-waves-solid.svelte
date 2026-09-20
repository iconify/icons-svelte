<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj0xv2bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0xv2bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:five-waves-solid" {...props}></Icon>
