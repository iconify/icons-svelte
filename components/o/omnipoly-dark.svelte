<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2f6qddde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e2f6qddde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnipoly-dark" {...props}></Icon>
