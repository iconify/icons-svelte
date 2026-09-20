<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qipqjpbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qipqjpbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:filter" {...props}></Icon>
