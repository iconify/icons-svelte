<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trm71o2xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="trm71o2xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:docpad" {...props}></Icon>
