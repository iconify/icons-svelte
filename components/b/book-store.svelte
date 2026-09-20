<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjx5ey33j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qjx5ey33j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:book-store" {...props}></Icon>
