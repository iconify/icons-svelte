<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p42wrwb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p42wrwb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:casaos-light" {...props}></Icon>
