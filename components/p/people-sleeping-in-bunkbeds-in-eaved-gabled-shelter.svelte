<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2gs35byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w2gs35byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-gabled-shelter" {...props}></Icon>
