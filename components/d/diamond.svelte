<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3_7p6bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3_7p6bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:diamond" {...props}></Icon>
