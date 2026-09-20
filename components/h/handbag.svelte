<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xultr8o4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xultr8o4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:handbag" {...props}></Icon>
