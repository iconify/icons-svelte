<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmw-1gb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mmw-1gb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-corner-up-left-keyboard-top-arrow-left-up" {...props}></Icon>
