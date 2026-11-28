<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i3-29jb8c.css';
import '../../css/g/g25wxlbyx.css';
import '../../css/d/dvfmgjbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i3-29jb8c"/><path class="g25wxlbyx"/><path class="dvfmgjbui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-through-line" {...props}></Icon>
