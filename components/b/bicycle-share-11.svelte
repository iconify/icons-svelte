<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-9b1fark.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="i-9b1fark"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bicycle-share-11" {...props}></Icon>
