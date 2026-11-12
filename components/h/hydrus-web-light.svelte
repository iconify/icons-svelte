<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfh4nmb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pfh4nmb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hydrus-web-light" {...props}></Icon>
