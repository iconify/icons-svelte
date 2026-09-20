<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9ds4yb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9ds4yb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:insert-after" {...props}></Icon>
