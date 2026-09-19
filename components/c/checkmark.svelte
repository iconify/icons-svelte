<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b276a-bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="b276a-bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:checkmark" {...props}></Icon>
