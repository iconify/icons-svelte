<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j32nkob6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j32nkob6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-envelope-right-with-euro" {...props}></Icon>
