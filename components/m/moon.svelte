<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv2ndra2q.css';
import '../../css/m/mgbb3achs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv2ndra2q"/><path class="mgbb3achs wm-deco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:moon" {...props}></Icon>
