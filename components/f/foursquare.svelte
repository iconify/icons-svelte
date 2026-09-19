<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e079j9kul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1216,"height":1664};
const content = `<path class="e079j9kul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:foursquare" {...props}></Icon>
