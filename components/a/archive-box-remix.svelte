<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np4zpu2je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="np4zpu2je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:archive-box-remix" {...props}></Icon>
