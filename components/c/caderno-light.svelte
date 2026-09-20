<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf-25ebtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sf-25ebtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:caderno-light" {...props}></Icon>
