<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se4hh51qv.css';
import '../../css/e/e0fc6m9hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="se4hh51qv"/><path class="e0fc6m9hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:networking-toolbox" {...props}></Icon>
