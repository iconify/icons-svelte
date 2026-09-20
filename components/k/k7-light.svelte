<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqkghtbcd.css';
import '../../css/j/jnr5slbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dqkghtbcd"/><path class="jnr5slbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:k7-light" {...props}></Icon>
