<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wlah1cbhg.css';
import '../../css/r/rhsxb9bdp.css';
import '../../css/h/husi78b2l.css';
import '../../css/x/xfyd-ebwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wlah1cbhg"/><path class="rhsxb9bdp"/><path class="husi78b2l"/><path class="xfyd-ebwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-checks-duo" {...props}></Icon>
