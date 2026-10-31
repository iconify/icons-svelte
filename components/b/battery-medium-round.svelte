<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo8q_vbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo8q_vbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-medium-round" {...props}></Icon>
