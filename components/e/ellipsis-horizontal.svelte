<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7d-ndb_c.css';
import '../../css/u/uffdfabip.css';
import '../../css/p/pyalxlbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><circle class="uffdfabip"/><circle class="pyalxlbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ellipsis-horizontal" {...props}></Icon>
