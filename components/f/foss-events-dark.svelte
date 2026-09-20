<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv9ej7bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qv9ej7bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:foss-events-dark" {...props}></Icon>
