<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q17t251rw.css';
import '../../css/y/yvf9cwdfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q17t251rw"/><path class="yvf9cwdfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:image-plus" {...props}></Icon>
