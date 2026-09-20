<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogni7k6ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ogni7k6ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nanosmart-light" {...props}></Icon>
