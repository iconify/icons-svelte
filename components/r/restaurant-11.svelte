<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w10uxx11n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="w10uxx11n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:restaurant-11" {...props}></Icon>
