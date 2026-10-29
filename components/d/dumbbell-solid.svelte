<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le-25ab2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le-25ab2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dumbbell-solid" {...props}></Icon>
