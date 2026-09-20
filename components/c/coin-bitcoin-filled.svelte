<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha34h3phx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha34h3phx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:coin-bitcoin-filled" {...props}></Icon>
