<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/honyfv0bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="honyfv0bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:basic-memory-light" {...props}></Icon>
