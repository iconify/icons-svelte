<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9gcr-yud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m9gcr-yud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dribbble-square" {...props}></Icon>
