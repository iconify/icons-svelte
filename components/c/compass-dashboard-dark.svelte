<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilot6bcet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilot6bcet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:compass-dashboard-dark" {...props}></Icon>
