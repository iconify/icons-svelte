<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4sditc7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q4sditc7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:garlic-hub-dark" {...props}></Icon>
