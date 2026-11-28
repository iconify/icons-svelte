<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/oszrj5blc.css';
import '../../css/i/inmwkd4ia.css';
import '../../css/b/brsnfwb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="oszrj5blc"/><path class="inmwkd4ia"/><path class="brsnfwb1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:intersect" {...props}></Icon>
