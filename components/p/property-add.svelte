<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuzg7bx1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuzg7bx1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:property-add" {...props}></Icon>
