<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d37911_pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d37911_pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:baby" {...props}></Icon>
