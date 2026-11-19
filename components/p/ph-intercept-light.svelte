<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxy12r89z.css';
import '../../css/j/jdijwxbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rxy12r89z"/><path class="jdijwxbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ph-intercept-light" {...props}></Icon>
