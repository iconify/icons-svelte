<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l9hplwb4s.css';
import '../../css/o/o49mt59vz.css';
import '../../css/u/uv10-xb0c.css';
import '../../css/l/ltjbqib6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="l9hplwb4s"/><path class="o49mt59vz"/><circle class="uv10-xb0c"/><circle class="ltjbqib6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:ambulance" {...props}></Icon>
