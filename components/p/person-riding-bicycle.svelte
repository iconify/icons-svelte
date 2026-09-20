<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2-1b2hsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i2-1b2hsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-bicycle" {...props}></Icon>
