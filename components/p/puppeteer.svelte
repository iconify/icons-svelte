<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozeyqcctf.css';
import '../../css/p/paymb2lad.css';
import '../../css/f/fmnfphbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ozeyqcctf"/><path class="paymb2lad"/><path class="fmnfphbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:puppeteer" {...props}></Icon>
