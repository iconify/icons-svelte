<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6yy04fix.css';
import '../../css/o/o4u834bpr.css';
import '../../css/a/avmk686_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6yy04fix"/><path class="o4u834bpr"/><path class="avmk686_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-square-bold-duotone" {...props}></Icon>
