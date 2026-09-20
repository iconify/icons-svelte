<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oojeu4z1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oojeu4z1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:donetick-dark" {...props}></Icon>
