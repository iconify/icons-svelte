<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aen4qlbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aen4qlbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ace-stream-light" {...props}></Icon>
