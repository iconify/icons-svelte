<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkz86tbnb.css';
import '../../css/t/tlq2l5bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkz86tbnb secondary"/><path class="primary tlq2l5bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bluesky-duo" {...props}></Icon>
