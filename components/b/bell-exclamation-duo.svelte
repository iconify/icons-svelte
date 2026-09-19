<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o5f05obqd.css';
import '../../css/i/idcl1o6gj.css';
import '../../css/x/xqz-l_kst.css';
import '../../css/n/n_9fa2idq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="o5f05obqd"/><path class="idcl1o6gj"/><path class="xqz-l_kst"/><path class="n_9fa2idq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-exclamation-duo" {...props}></Icon>
