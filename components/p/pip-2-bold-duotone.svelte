<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixky28b1f.css';
import '../../css/y/ye90rbccq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixky28b1f"/><path class="ye90rbccq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pip-2-bold-duotone" {...props}></Icon>
