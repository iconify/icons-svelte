<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhahj9bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1991.3,"height":2143.2};
const content = `<path class="mhahj9bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:airbnb" {...props}></Icon>
