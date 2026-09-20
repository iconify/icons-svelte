<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5geo5bod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v5geo5bod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notifuse-dark" {...props}></Icon>
