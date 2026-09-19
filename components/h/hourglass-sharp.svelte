<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0eda4_8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i0eda4_8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:hourglass-sharp" {...props}></Icon>
