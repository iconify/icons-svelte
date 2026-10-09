<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt1n5vgcf.css';
import '../../css/a/asggcsbcx.css';
import '../../css/p/pzsn-8bob.css';
import '../../css/b/b7d87qvzu.css';
import '../../css/c/cpm9ckb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gt1n5vgcf"/><path class="asggcsbcx"/><path class="pzsn-8bob"/><path class="b7d87qvzu"/><path class="cpm9ckb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drone-20-bold" {...props}></Icon>
