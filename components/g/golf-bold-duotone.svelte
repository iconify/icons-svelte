<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzdv_ccir.css';
import '../../css/x/x9-rwuyde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="zzdv_ccir"/><path class="x9-rwuyde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:golf-bold-duotone" {...props}></Icon>
