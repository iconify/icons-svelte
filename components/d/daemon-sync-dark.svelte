<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odvo0kyvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odvo0kyvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:daemon-sync-dark" {...props}></Icon>
