<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_mykyb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_mykyb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amd-dark" {...props}></Icon>
