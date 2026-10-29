<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv5jltqeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv5jltqeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:columns-4" {...props}></Icon>
