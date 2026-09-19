<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f82_z8gvp.css';
import '../../css/e/eqii1hm4p.css';
import '../../css/w/w-d6ddz8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="f82_z8gvp"/><path class="eqii1hm4p"/><path class="w-d6ddz8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:recent-views-sort" {...props}></Icon>
