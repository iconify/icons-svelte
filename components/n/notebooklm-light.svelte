<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7wwqbb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u7wwqbb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notebooklm-light" {...props}></Icon>
