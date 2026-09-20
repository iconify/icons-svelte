<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/i/ipgfq6bhn.css';
import '../../css/k/k4z7zsbhp.css';
import '../../css/b/bqt1fxbrt.css';
import '../../css/n/n_h7qlzuy.css';
import '../../css/c/c9mfofy0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><ellipse class="ipgfq6bhn"/><circle class="k4z7zsbhp"/><path class="bqt1fxbrt"/><ellipse class="n_h7qlzuy"/><path class="c9mfofy0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hushed-face" {...props}></Icon>
