<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2aj5q4dy.css';
import '../../css/w/wvwuueb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h2aj5q4dy"/><path class="wvwuueb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-superset" {...props}></Icon>
