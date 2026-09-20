<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6e1offvk.css';
import '../../css/a/a_xac3lyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s6e1offvk"/><path class="a_xac3lyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reitti-light" {...props}></Icon>
