<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-swyr_3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":146};
const content = `<path class="v-swyr_3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:instagram-legacy" {...props}></Icon>
