<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bugd6-bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bugd6-bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-down" {...props}></Icon>
