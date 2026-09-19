<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx7ll9vpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="sx7ll9vpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:bookmark" {...props}></Icon>
