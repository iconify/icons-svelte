<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7d-ndb_c.css';
import '../../css/i/if1j4p61s.css';
import '../../css/b/bqprax02h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><path class="if1j4p61s"/><path class="bqprax02h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:nuclear-sharp" {...props}></Icon>
