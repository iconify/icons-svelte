<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8ld33dpy.css';
import '../../css/x/x7pqpmbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8ld33dpy"/><path clip-rule="evenodd" class="x7pqpmbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:buildings-2-bold-duotone" {...props}></Icon>
