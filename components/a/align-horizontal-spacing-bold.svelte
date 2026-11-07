<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co9si1b_r.css';
import '../../css/a/ansfvlgtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="co9si1b_r"/><path class="ansfvlgtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-horizontal-spacing-bold" {...props}></Icon>
