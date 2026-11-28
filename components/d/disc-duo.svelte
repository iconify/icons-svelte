<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1x1djbzo.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/b/blc8-wb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1x1djbzo secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="blc8-wb1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:disc-duo" {...props}></Icon>
