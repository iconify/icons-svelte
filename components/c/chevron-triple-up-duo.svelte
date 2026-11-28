<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ixactvbks.css';
import '../../css/r/rsml70e1r.css';
import '../../css/q/qggd_up0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ixactvbks"/><path class="rsml70e1r"/><path class="qggd_up0u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-triple-up-duo" {...props}></Icon>
