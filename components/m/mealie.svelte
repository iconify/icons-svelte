<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6-h_042q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h6-h_042q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mealie" {...props}></Icon>
