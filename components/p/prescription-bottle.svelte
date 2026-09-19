<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njk0u4giu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="njk0u4giu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:prescription-bottle" {...props}></Icon>
