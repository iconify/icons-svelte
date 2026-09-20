<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8xpn1iix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m8xpn1iix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:louisiana-with-capital-star" {...props}></Icon>
