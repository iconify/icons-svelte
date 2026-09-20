<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5rxkyb0h.css';
import '../../css/i/i9q0xsztd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x5rxkyb0h"/><path class="i9q0xsztd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:rotate-anticlockwise-16" {...props}></Icon>
