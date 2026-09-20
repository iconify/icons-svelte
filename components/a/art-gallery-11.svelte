<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd4yuk13a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="fd4yuk13a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:art-gallery-11" {...props}></Icon>
