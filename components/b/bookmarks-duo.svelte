<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nifb8ib4x.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p62ofhric.css';
import '../../css/u/ubuapjbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nifb8ib4x secondary"/><g class="dt0cm9dhy primary"><path class="p62ofhric"/><path class="ubuapjbpy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmarks-duo" {...props}></Icon>
