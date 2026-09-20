<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih95x1b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ih95x1b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:remove-eye" {...props}></Icon>
