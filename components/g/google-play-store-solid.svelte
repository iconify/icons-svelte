<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c965ddcsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c965ddcsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:google-play-store-solid" {...props}></Icon>
