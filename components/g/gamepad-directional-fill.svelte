<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljdyadjeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljdyadjeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gamepad-directional-fill" {...props}></Icon>
