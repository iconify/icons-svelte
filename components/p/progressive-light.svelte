<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvmcp3bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hvmcp3bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:progressive-light" {...props}></Icon>
