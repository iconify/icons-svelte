<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld8w7hb7k.css';
import '../../css/s/s6u87zegn.css';
import '../../css/c/cqnbl8q7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="ld8w7hb7k"/><rect class="s6u87zegn"/><path class="cqnbl8q7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:battery-half" {...props}></Icon>
