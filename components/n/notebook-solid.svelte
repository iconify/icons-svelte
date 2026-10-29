<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjgn7172q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjgn7172q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:notebook-solid" {...props}></Icon>
