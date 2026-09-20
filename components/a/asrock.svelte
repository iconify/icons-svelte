<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4f00vbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g4f00vbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asrock" {...props}></Icon>
