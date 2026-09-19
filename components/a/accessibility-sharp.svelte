<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3j-vtbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u3j-vtbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:accessibility-sharp" {...props}></Icon>
