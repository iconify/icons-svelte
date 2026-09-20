<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmcpxvbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vmcpxvbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:piggy-bank-solid" {...props}></Icon>
