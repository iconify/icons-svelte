<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wufnt-66i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wufnt-66i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:it-tools-light" {...props}></Icon>
