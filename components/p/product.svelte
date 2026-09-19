<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjc7jhbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjc7jhbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:product" {...props}></Icon>
