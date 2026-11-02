<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj73_9b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj73_9b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camera-2-fill" {...props}></Icon>
