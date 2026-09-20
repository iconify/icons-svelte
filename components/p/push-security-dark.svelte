<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1nmm7blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x1nmm7blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:push-security-dark" {...props}></Icon>
