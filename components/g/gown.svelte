<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhxgfacuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xhxgfacuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:gown" {...props}></Icon>
