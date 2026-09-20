<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wap2w4btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wap2w4btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:nurse-assistant-emergency-remix" {...props}></Icon>
