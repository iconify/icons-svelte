<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sozdzcb0a.css';
import '../../css/t/ttno82btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sozdzcb0a"/><path class="ttno82btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-network-filled" {...props}></Icon>
