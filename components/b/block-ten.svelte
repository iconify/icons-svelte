<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g54fotb1f.css';
import '../../css/d/d70u10bbk.css';
import '../../css/d/dov8vg2gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="g54fotb1f"><path class="d70u10bbk"/><path class="dov8vg2gk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:block-ten" {...props}></Icon>
