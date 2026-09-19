<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgs6ycb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fgs6ycb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:buildkite" {...props}></Icon>
