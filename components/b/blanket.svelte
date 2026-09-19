<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl1qd3ihr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl1qd3ihr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:blanket" {...props}></Icon>
