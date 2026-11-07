<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lxnzn9nmw.css';
import '../../css/j/j56zj4bua.css';
import '../../css/n/n0kyqub_b.css';
import '../../css/d/d8p_c0bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lxnzn9nmw"/><path class="j56zj4bua"/><path class="n0kyqub_b"/><path class="d8p_c0bee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cardholder-line-duotone" {...props}></Icon>
