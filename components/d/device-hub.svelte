<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk02wmbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="qk02wmbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:device-hub" {...props}></Icon>
