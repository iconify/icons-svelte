<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u325fvbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u325fvbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:crop" {...props}></Icon>
