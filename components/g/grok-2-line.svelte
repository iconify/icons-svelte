<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7mqf2bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7mqf2bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grok-2-line" {...props}></Icon>
