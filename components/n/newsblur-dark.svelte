<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4viabbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r4viabbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:newsblur-dark" {...props}></Icon>
