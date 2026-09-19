<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4y0izbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w4y0izbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:recordingtape" {...props}></Icon>
