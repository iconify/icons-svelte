<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h0z33lbii.css';
import '../../css/v/v9c3zo18p.css';
import '../../css/f/f0kck1bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h0z33lbii"/><path class="v9c3zo18p"/><path class="f0kck1bsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-merge-duo" {...props}></Icon>
