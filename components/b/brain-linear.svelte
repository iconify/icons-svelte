<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/ltvp4bbbj.css';
import '../../css/r/r226xsbyq.css';
import '../../css/k/kqj26io4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ltvp4bbbj"/><path class="r226xsbyq"/><path class="kqj26io4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:brain-linear" {...props}></Icon>
