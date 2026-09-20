<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-qhtt8zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s-qhtt8zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-envelope-right-with-rupee" {...props}></Icon>
