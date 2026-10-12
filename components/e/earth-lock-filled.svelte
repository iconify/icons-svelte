<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txs0h11aa.css';
import '../../css/f/fgo78vant.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txs0h11aa"/><path clip-rule="evenodd" class="fgo78vant"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:earth-lock-filled" {...props}></Icon>
