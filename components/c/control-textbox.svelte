<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ockwfkbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ockwfkbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:control-textbox" {...props}></Icon>
