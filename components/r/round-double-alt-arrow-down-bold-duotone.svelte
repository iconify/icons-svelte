<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c77vne7ui.css';
import '../../css/w/w177c5zkh.css';
import '../../css/n/nidoksbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c77vne7ui"/><path class="w177c5zkh"/><path class="nidoksbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-down-bold-duotone" {...props}></Icon>
