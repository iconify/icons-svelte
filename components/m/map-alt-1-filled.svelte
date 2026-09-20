<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbb6zhbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jbb6zhbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:map-alt-1-filled" {...props}></Icon>
