<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc8x5ib_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc8x5ib_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:component" {...props}></Icon>
