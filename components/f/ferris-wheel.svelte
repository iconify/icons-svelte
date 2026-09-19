<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo_j92bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lo_j92bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ferris-wheel" {...props}></Icon>
