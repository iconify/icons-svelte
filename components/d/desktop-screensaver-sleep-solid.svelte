<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7gu3tban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j7gu3tban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:desktop-screensaver-sleep-solid" {...props}></Icon>
