<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu8469bse.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pq36bjb0y.css';
import '../../css/p/pzjv5fl5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu8469bse secondary"/><g class="dt0cm9dhy primary"><path class="pq36bjb0y"/><path class="pzjv5fl5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mirror-duo" {...props}></Icon>
