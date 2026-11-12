<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5upftd6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5upftd6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-share" {...props}></Icon>
