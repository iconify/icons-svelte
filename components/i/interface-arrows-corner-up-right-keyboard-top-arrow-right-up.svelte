<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1zjupb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w1zjupb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-corner-up-right-keyboard-top-arrow-right-up" {...props}></Icon>
