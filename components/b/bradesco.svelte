<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlvpmbbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":123,"height":23.1};
const content = `<path class="vlvpmbbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bradesco" {...props}></Icon>
