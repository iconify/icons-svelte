<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vyn2gq-gt.css';
import '../../css/k/kt93orw5x.css';
import '../../css/t/tbf9wf6kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vyn2gq-gt"/><path class="kt93orw5x"/><path class="tbf9wf6kd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:croissant" {...props}></Icon>
