<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykalgvbci.css';
import '../../css/y/yn92p7rip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ykalgvbci"/><path class="yn92p7rip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aspects-filled" {...props}></Icon>
