<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxlgg64z.css';
import '../../css/d/d9g_0nbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="d9g_0nbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:clock-ten" {...props}></Icon>
