<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt3j8_u0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt3j8_u0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:football-pitch" {...props}></Icon>
