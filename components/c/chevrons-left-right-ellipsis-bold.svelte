<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz625mb3h.css';
import '../../css/v/vfll34fsr.css';
import '../../css/v/v69b44b0n.css';
import '../../css/u/uwtypmg-l.css';
import '../../css/j/jo4v5sbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz625mb3h"/><path class="vfll34fsr"/><path class="v69b44b0n"/><path class="uwtypmg-l"/><path class="jo4v5sbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-left-right-ellipsis-bold" {...props}></Icon>
