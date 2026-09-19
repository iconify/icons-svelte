<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlsqcp-7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tlsqcp-7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:exclamationmark-square" {...props}></Icon>
