<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh5onpn0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zh5onpn0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:code-filled" {...props}></Icon>
