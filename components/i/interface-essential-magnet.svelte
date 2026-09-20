<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn_jahutr.css';
import '../../css/q/qtvna5bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hn_jahutr"/><path class="qtvna5bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-magnet" {...props}></Icon>
