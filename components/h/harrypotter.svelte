<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxggr_brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":886};
const content = `<path class="mxggr_brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:harrypotter" {...props}></Icon>
