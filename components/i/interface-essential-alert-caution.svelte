<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1tihnb2l.css';
import '../../css/q/qersjhb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s1tihnb2l"/><path class="qersjhb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-alert-caution" {...props}></Icon>
