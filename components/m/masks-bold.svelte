<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0e1_pbyx.css';
import '../../css/a/a7x3g_3uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0e1_pbyx"/><path clip-rule="evenodd" class="a7x3g_3uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:masks-bold" {...props}></Icon>
