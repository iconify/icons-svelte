<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc9_9gp3w.css';
import '../../css/c/cqrepab2x.css';
import '../../css/y/yd6ryz9vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pc9_9gp3w"/><path class="cqrepab2x"/><path class="yd6ryz9vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamanager" {...props}></Icon>
