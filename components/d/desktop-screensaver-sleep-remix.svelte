<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnhm3dmjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnhm3dmjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:desktop-screensaver-sleep-remix" {...props}></Icon>
