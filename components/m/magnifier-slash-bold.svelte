<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa6kukbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xa6kukbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-slash-bold" {...props}></Icon>
