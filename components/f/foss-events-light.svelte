<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzp2_-t5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzp2_-t5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:foss-events-light" {...props}></Icon>
