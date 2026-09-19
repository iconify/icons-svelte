<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqnp4cb9p.css';
import '../../css/q/q0c7o4bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<ellipse class="nqnp4cb9p"/><circle class="q0c7o4bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:decimal-stroke-12" {...props}></Icon>
