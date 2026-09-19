<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jloxq3b0a.css';
import '../../css/t/t01qni1jx.css';
import '../../css/s/s11n-zb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jloxq3b0a"/><path class="t01qni1jx"/><path class="s11n-zb6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-tag" {...props}></Icon>
