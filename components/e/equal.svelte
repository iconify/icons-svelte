<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otu6l8b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otu6l8b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:equal" {...props}></Icon>
