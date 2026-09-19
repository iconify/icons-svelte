<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhr69gdnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhr69gdnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:boat-filled" {...props}></Icon>
