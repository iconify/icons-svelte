<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8m4h0bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v8m4h0bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bluetooth-20-bold" {...props}></Icon>
