<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umi_2wm3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umi_2wm3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-locked-fill" {...props}></Icon>
