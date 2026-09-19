<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h68a5vtzz.css';
import '../../css/h/hp_yerj1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="h68a5vtzz"/><path class="hp_yerj1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-notification" {...props}></Icon>
