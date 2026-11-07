<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gswtq35or.css';
import '../../css/r/r10rxstew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gswtq35or"/><path class="r10rxstew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-add-angle-bold-duotone" {...props}></Icon>
