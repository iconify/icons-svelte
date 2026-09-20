<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbmc7blgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tbmc7blgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:fullscreen-active" {...props}></Icon>
