<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl0knccre.css';
import '../../css/i/iqt0h4b6a.css';
import '../../css/x/xncxpgo4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vl0knccre"/><path class="iqt0h4b6a"/><path class="xncxpgo4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-link" {...props}></Icon>
