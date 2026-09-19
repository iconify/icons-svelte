<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg3b3wd3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3b3wd3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heading-3" {...props}></Icon>
