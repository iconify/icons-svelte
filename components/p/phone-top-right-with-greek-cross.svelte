<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b71gbhpxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b71gbhpxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-top-right-with-greek-cross" {...props}></Icon>
