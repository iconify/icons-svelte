<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a69cznbzg.css';
import '../../css/c/ckrv68b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a69cznbzg"/><path class="ckrv68b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bone-bold-duotone" {...props}></Icon>
