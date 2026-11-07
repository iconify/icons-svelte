<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohfan4oud.css';
import '../../css/b/b-_nic0_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohfan4oud"/><path class="b-_nic0_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-bold-duotone" {...props}></Icon>
