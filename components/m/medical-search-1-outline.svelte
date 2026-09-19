<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d6zxgccaz.css';
import '../../css/l/la_6nmkfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="d6zxgccaz"/><path clip-rule="evenodd" class="la_6nmkfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:medical-search-1-outline" {...props}></Icon>
