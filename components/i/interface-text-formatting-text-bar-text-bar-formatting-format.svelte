<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vokuk34lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vokuk34lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-text-bar-text-bar-formatting-format" {...props}></Icon>
