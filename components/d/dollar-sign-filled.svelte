<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvxoq3cbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvxoq3cbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:dollar-sign-filled" {...props}></Icon>
