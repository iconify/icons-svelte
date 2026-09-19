<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlaltv3jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlaltv3jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:diamond-plus" {...props}></Icon>
