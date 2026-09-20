<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2ykfpbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="n2ykfpbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-left-arrow-keyboard-left" {...props}></Icon>
