<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjjw5bber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":488};
const content = `<path class="rjjw5bber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:github" {...props}></Icon>
