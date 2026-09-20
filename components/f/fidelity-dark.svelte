<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r527d0bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r527d0bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fidelity-dark" {...props}></Icon>
