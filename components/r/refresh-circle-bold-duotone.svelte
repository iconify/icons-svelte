<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrxlgg64z.css';
import '../../css/p/pwgp6wb0l.css';
import '../../css/g/gw5xq8brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="pwgp6wb0l"/><path class="gw5xq8brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:refresh-circle-bold-duotone" {...props}></Icon>
