<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep5i4rb8t.css';
import '../../css/r/rd02-vf7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ep5i4rb8t"/><path class="rd02-vf7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cookcli" {...props}></Icon>
