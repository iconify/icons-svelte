<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdtm0qhix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdtm0qhix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitbundle-light" {...props}></Icon>
