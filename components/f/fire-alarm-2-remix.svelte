<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuv44oplk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tuv44oplk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fire-alarm-2-remix" {...props}></Icon>
