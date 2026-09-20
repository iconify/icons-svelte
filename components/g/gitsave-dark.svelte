<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg-4ik0ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lg-4ik0ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitsave-dark" {...props}></Icon>
