<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1u6ybcci.css';
import '../../css/s/s_wtzvbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1u6ybcci"/><path class="s_wtzvbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-switch" {...props}></Icon>
