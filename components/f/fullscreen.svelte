<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhab1oxmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhab1oxmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:fullscreen" {...props}></Icon>
