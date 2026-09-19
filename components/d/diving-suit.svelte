<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5cg8fb9r.css';
import '../../css/f/fe_6t6d0u.css';
import '../../css/y/y4mbm7bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="fe_6t6d0u"/><path class="y4mbm7bnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:diving-suit" {...props}></Icon>
