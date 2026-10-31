<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv380lbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv380lbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-text-fill-round" {...props}></Icon>
