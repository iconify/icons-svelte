<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctf7tpbxx.css';
import '../../css/i/i_23a8b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctf7tpbxx"/><path class="i_23a8b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-left-bold-duotone" {...props}></Icon>
