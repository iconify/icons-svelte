<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv6xn7b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv6xn7b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:grip-horizontal" {...props}></Icon>
