<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aubbjwbfk.css';
import '../../css/r/rp9ikhbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aubbjwbfk"/><path class="rp9ikhbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oak-identity" {...props}></Icon>
