<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfb1qvbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bfb1qvbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nodebb-light" {...props}></Icon>
