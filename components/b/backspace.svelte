<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzh3ahbvr.css';
import '../../css/f/f5tkpn2pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vzh3ahbvr"/><path class="f5tkpn2pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:backspace" {...props}></Icon>
