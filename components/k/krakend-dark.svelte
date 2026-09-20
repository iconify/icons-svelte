<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjfi1hblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hjfi1hblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:krakend-dark" {...props}></Icon>
