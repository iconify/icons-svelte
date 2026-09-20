<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/ldfiv-13q.css';
import '../../css/t/tnf8gbb-i.css';
import '../../css/u/uiwsg29tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ldfiv-13q"/><path class="tnf8gbb-i"/><path class="uiwsg29tk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-cross-linear" {...props}></Icon>
