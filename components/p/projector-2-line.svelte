<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4mnxrcmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4mnxrcmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:projector-2-line" {...props}></Icon>
