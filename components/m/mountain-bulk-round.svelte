<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh3x8xafe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh3x8xafe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mountain-bulk-round" {...props}></Icon>
