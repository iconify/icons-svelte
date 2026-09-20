<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf06pbs2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lf06pbs2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jula-dark" {...props}></Icon>
