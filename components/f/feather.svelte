<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6fiy_b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6fiy_b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:feather" {...props}></Icon>
