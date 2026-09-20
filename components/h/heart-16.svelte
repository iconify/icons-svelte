<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p64taib3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p64taib3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:heart-16" {...props}></Icon>
