<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s81rsdbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="s81rsdbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-sub-script-text-formatting-subscript-format" {...props}></Icon>
