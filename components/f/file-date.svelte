<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/fqwagjb6j.css';
import '../../css/c/cnuln6twg.css';
import '../../css/s/sfbrjpc4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="fqwagjb6j"/><circle class="cnuln6twg"/><path class="sfbrjpc4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-date" {...props}></Icon>
