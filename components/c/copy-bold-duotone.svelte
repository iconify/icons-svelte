<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwfa9_-5x.css';
import '../../css/m/mtplmt03a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwfa9_-5x"/><path class="mtplmt03a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-bold-duotone" {...props}></Icon>
