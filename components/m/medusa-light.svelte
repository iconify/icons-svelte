<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia_n5zeau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ia_n5zeau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medusa-light" {...props}></Icon>
