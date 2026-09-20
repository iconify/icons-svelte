<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvox8lb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvox8lb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-5-filled" {...props}></Icon>
