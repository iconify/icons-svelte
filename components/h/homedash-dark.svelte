<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe_54rbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oe_54rbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homedash-dark" {...props}></Icon>
