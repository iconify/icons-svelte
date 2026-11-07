<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcnfpbj7d.css';
import '../../css/p/pzl1-q55o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcnfpbj7d"/><path class="pzl1-q55o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-minimalistic-bold-duotone" {...props}></Icon>
