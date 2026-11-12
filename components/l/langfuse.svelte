<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq6qj3b9f.css';
import '../../css/d/d_ic3kbus.css';
import '../../css/x/xv20pn3tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wq6qj3b9f"/><path class="d_ic3kbus"/><path class="xv20pn3tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:langfuse" {...props}></Icon>
