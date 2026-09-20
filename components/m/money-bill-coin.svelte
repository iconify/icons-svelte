<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lok1vab1w.css';
import '../../css/a/aukxkfh_w.css';
import '../../css/l/l50czp3km.css';
import '../../css/z/zg2dzdq3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lok1vab1w"/><path class="aukxkfh_w"/><path class="l50czp3km"/><path class="zg2dzdq3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-bill-coin" {...props}></Icon>
