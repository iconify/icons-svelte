<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ausm4qbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ausm4qbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-unlock-bold" {...props}></Icon>
