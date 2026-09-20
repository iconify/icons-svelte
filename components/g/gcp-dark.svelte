<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/q/qtxvqek9n.css';
import '../../css/i/if4rj7bxx.css';
import '../../css/y/y98e5yb6x.css';
import '../../css/o/otcpv5h_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path class="qtxvqek9n"/><path class="if4rj7bxx"/><path class="y98e5yb6x"/><path class="otcpv5h_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:gcp-dark" {...props}></Icon>
