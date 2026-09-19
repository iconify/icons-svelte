<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k371edcsm.css';
import '../../css/a/aaxtufr3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k371edcsm"/><path class="aaxtufr3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:badge-exclamation" {...props}></Icon>
