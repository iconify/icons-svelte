<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w04165mul.css';
import '../../css/o/on5h-v5us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w04165mul"/><path class="on5h-v5us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:import-outline" {...props}></Icon>
