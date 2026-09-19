<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/c/c1_zvmcqj.css';
import '../../css/z/zr7_nbbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="c1_zvmcqj"/><path class="zr7_nbbae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:hidden-outline" {...props}></Icon>
