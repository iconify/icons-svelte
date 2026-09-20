<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3w1466qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3w1466qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:novu-light" {...props}></Icon>
