<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/fcpug8qfn.css';
import '../../css/i/i4gf_wb7q.css';
import '../../css/m/m_hxi5hql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="fcpug8qfn"/><path class="i4gf_wb7q"/><path class="m_hxi5hql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:coins" {...props}></Icon>
