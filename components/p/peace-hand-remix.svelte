<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f118krgzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f118krgzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:peace-hand-remix" {...props}></Icon>
