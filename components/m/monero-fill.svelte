<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfa8f7bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfa8f7bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:monero-fill" {...props}></Icon>
