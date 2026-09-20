<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qdd9k55bw.css';
import '../../css/g/gtr9mcbgh.css';
import '../../css/n/n_5_uwbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qdd9k55bw"/><path class="gtr9mcbgh"/><path class="n_5_uwbjy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bitcoin-card" {...props}></Icon>
