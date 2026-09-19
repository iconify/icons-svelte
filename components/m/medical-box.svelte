<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/crqzezbkc.css';
import '../../css/p/p9rx95bqb.css';
import '../../css/c/cp1palbkb.css';
import '../../css/e/e6kad7bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="crqzezbkc"/><path class="p9rx95bqb"/><path class="cp1palbkb"/><path class="e6kad7bsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:medical-box" {...props}></Icon>
