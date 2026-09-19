<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q00u4lbrm.css';
import '../../css/q/q3ouhtb3r.css';
import '../../css/f/fv17wn2rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q00u4lbrm"/><circle class="q3ouhtb3r"/><path class="fv17wn2rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:baseball-outline" {...props}></Icon>
