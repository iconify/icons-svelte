<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0w2_eb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u0w2_eb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lululemon-light" {...props}></Icon>
