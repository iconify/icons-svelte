<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpxmdzbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dpxmdzbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circle-with-fallout-shelter-symbol" {...props}></Icon>
