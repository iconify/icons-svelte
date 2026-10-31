<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf12pkbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf12pkbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-1-fill-round" {...props}></Icon>
