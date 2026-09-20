<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g69cwyy3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g69cwyy3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:contabo-dark" {...props}></Icon>
