<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs6magbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rs6magbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dialysis-alt-24px" {...props}></Icon>
