<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szpeuiw3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szpeuiw3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:money-wallet-open-bold" {...props}></Icon>
