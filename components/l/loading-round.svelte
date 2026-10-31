<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxt7g3rhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxt7g3rhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:loading-round" {...props}></Icon>
