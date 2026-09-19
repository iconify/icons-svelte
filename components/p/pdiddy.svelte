<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2uz6p22g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c2uz6p22g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pdiddy" {...props}></Icon>
