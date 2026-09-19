<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv5qt_s0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="qv5qt_s0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:arrow-right" {...props}></Icon>
