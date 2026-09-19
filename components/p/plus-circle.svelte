<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq_l1x1ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="aq_l1x1ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:plus-circle" {...props}></Icon>
