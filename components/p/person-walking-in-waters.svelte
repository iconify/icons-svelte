<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jknwspb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jknwspb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-in-waters" {...props}></Icon>
