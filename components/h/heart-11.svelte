<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii6g86ohh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ii6g86ohh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:heart-11" {...props}></Icon>
