<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f81p3t1eb.css';
import '../../css/g/go_f49b4o.css';
import '../../css/h/h1_u2g9co.css';
import '../../css/o/ogj4hdl4n.css';
import '../../css/e/e7-_s6bak.css';
import '../../css/w/wm5y74tkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="f81p3t1eb"/><circle class="go_f49b4o"/><circle class="h1_u2g9co"/><circle class="ogj4hdl4n"/><circle class="e7-_s6bak"/><path class="wm5y74tkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:coronavirus" {...props}></Icon>
