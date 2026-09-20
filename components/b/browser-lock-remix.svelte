<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9uzlgk-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r9uzlgk-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-lock-remix" {...props}></Icon>
