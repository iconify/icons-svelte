<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/e/esx2m_bgj.css';
import '../../css/k/kq63r2b2y.css';
import '../../css/h/hr0zsab8t.css';
import '../../css/b/bidljcb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="esx2m_bgj"/><path class="kq63r2b2y"/><path class="hr0zsab8t"/><path class="bidljcb4r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:calendar" {...props}></Icon>
