<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lowqi3bit.css';
import '../../css/n/nm733ibre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lowqi3bit"/><path class="nm733ibre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:business-coaching-whistle" {...props}></Icon>
