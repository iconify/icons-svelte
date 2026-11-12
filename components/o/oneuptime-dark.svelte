<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1zc5nbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1zc5nbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oneuptime-dark" {...props}></Icon>
