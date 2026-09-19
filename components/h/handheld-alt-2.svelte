<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rayco9bbe.css';
import '../../css/p/p1v9mob6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rayco9bbe"/><path class="p1v9mob6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:handheld-alt-2" {...props}></Icon>
