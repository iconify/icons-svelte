<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7l_pfh9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x7l_pfh9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pin" {...props}></Icon>
