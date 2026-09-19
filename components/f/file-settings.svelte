<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/fqwagjb6j.css';
import '../../css/o/orjx92biv.css';
import '../../css/m/m1mo2dbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="fqwagjb6j"/><circle class="orjx92biv"/><path class="m1mo2dbtk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-settings" {...props}></Icon>
