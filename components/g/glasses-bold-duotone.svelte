<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fudxizbvs.css';
import '../../css/x/x0_riwbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fudxizbvs"/><path class="x0_riwbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:glasses-bold-duotone" {...props}></Icon>
