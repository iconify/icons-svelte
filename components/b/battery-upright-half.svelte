<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5sryr58s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t5sryr58s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-upright-half" {...props}></Icon>
