<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxwld8isk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxwld8isk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:prompt-fill-round" {...props}></Icon>
