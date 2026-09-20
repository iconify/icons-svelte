<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2cj1w83c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l2cj1w83c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:purpurmc-dark" {...props}></Icon>
