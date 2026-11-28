<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/in_hfigss.css';
import '../../css/w/w-4-qtbwu.css';
import '../../css/c/cgapqzb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="in_hfigss"/><path class="w-4-qtbwu"/><path class="cgapqzb1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:package" {...props}></Icon>
