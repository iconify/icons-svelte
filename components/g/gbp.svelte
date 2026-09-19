<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx2w4zb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1408};
const content = `<path class="mx2w4zb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:gbp" {...props}></Icon>
