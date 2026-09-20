<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jrp21-l0v.css';
import '../../css/t/ttwa5ubjw.css';
import '../../css/x/xzymugb3i.css';
import '../../css/k/kqrdbispo.css';
import '../../css/q/qpcpoabzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jrp21-l0v"/><path class="ttwa5ubjw"/><path class="xzymugb3i"/><path class="kqrdbispo"/><path class="qpcpoabzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:empty-wallet-change" {...props}></Icon>
