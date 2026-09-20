<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm56libzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pm56libzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agent-zero-dark" {...props}></Icon>
