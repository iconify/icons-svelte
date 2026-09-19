<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2x2vzbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b2x2vzbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pin-stroke-16" {...props}></Icon>
