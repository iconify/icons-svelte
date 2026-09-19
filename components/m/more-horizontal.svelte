<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds25a98oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds25a98oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-horizontal" {...props}></Icon>
