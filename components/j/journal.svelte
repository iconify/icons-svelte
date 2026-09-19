<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msakqth9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="msakqth9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:journal" {...props}></Icon>
