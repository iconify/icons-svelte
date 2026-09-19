<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6a4xtm3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6a4xtm3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:faucet-filled" {...props}></Icon>
