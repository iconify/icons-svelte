<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/a/a8c88x_pl.css';
import '../../css/h/ht2dh_bbo.css';
import '../../css/k/k628_qb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="a8c88x_pl"/><path class="ht2dh_bbo"/><path class="k628_qb9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:circle-alert" {...props}></Icon>
