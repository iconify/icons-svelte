<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/nsqnp5fhf.css';
import '../../css/m/m__36j5rb.css';
import '../../css/i/i-tcsr9te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="nsqnp5fhf"/><circle class="m__36j5rb"/><path class="i-tcsr9te"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:control" {...props}></Icon>
