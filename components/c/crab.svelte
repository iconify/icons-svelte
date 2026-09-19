<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/ronjz08st.css';
import '../../css/a/a8s_bgb4s.css';
import '../../css/e/e92ucll6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ronjz08st"/><rect class="a8s_bgb4s"/><path class="e92ucll6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:crab" {...props}></Icon>
