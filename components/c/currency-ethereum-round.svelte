<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzfkap_kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzfkap_kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-ethereum-round" {...props}></Icon>
