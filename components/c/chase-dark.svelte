<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2-0bgbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2-0bgbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chase-dark" {...props}></Icon>
