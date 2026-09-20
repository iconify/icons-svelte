<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-e1pwyws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="g-e1pwyws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:browser" {...props}></Icon>
