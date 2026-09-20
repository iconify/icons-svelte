<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in_ua9bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="in_ua9bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:peace-symbol-remix" {...props}></Icon>
