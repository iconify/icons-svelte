<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-2g-uwgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b-2g-uwgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-up-down" {...props}></Icon>
