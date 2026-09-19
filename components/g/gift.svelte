<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zavzvmbpq.css';
import '../../css/a/azcxndzqs.css';
import '../../css/k/kgseuybgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zavzvmbpq"/><path class="azcxndzqs"/><path class="kgseuybgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:gift" {...props}></Icon>
