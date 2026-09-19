<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnbf1scar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnbf1scar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:combine" {...props}></Icon>
