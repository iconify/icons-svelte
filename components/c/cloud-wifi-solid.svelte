<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6cyhdb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n6cyhdb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-wifi-solid" {...props}></Icon>
