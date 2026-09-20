<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7jcl1b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e7jcl1b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-waypoint-dark" {...props}></Icon>
