<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx4w7qbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xx4w7qbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:meshping-light" {...props}></Icon>
