<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8o30jhxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f8o30jhxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-right-arrow-right-keyboard" {...props}></Icon>
