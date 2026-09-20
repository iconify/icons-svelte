<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzk05gb5l.css';
import '../../css/d/d86a3vbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dzk05gb5l"/><path class="d86a3vbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:connectwise-screenconnect" {...props}></Icon>
