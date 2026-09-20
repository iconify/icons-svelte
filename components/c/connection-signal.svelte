<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb2n9ybdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gb2n9ybdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connection-signal" {...props}></Icon>
