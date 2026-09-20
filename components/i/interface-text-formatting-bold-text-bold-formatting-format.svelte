<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpadxjbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cpadxjbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-bold-text-bold-formatting-format" {...props}></Icon>
