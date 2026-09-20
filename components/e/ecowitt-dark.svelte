<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfetpsbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfetpsbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ecowitt-dark" {...props}></Icon>
