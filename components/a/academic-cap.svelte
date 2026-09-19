<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz24b1ysv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nz24b1ysv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:academic-cap" {...props}></Icon>
