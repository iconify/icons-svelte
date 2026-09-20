<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d20x7abpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d20x7abpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:openvpn-logo-block" {...props}></Icon>
