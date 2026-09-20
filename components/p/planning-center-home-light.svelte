<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9egjfbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9egjfbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-home-light" {...props}></Icon>
