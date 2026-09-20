<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeef006fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yeef006fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-keyboard-asterisk-1-asterisk-star-keyboard" {...props}></Icon>
