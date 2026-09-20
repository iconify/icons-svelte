<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrkchccet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrkchccet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-vr-filled" {...props}></Icon>
