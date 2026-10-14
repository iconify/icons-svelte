<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwan62b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwan62b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:certshell-light" {...props}></Icon>
