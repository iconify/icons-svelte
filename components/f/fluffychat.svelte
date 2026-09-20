<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ahb8bdh.css';
import '../../css/j/jsgezyb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_ahb8bdh"/><path class="jsgezyb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluffychat" {...props}></Icon>
