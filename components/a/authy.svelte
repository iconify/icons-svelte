<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnhwnduys.css';
import '../../css/h/hgfh0_gbr.css';
import '../../css/o/o-byg3jhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lnhwnduys"/><path class="hgfh0_gbr"/><path class="o-byg3jhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:authy" {...props}></Icon>
