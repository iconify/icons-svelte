<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge2r--jhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ge2r--jhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:arrow-circle-left" {...props}></Icon>
