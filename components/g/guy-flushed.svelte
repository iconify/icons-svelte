<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g169grb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g169grb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy-flushed" {...props}></Icon>
