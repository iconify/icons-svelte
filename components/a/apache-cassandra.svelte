<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbsvtbcxs.css';
import '../../css/r/raqx0nmsd.css';
import '../../css/a/aaaoe8b6g.css';
import '../../css/i/ii1y0ubpf.css';
import '../../css/e/ez443fbbf.css';
import '../../css/j/jer_9fuoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nbsvtbcxs"/><path class="raqx0nmsd"/><path class="aaaoe8b6g"/><path class="ii1y0ubpf"/><path class="ez443fbbf"/><path class="jer_9fuoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-cassandra" {...props}></Icon>
