<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6a5zmb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g6a5zmb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:boost-mobile" {...props}></Icon>
