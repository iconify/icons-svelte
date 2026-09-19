<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sg600_1ny.css';
import '../../css/f/fdqo9dbtl.css';
import '../../css/w/wv15rjmiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="sg600_1ny"/><path clip-rule="evenodd" class="fdqo9dbtl"/><path class="wv15rjmiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:people-plus" {...props}></Icon>
