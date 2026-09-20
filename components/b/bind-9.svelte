<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w96p14lvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w96p14lvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bind-9" {...props}></Icon>
