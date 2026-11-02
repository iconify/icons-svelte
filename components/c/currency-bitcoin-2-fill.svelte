<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu3lzyn3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu3lzyn3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-bitcoin-2-fill" {...props}></Icon>
