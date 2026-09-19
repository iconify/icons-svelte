<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z23r0f8ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z23r0f8ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cancel-01" {...props}></Icon>
