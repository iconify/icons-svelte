<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey3vbs2kb.css';
import '../../css/m/mx54xpbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ey3vbs2kb"/><path class="mx54xpbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:manage-protection" {...props}></Icon>
