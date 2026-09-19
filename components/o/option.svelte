<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebar8bcjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebar8bcjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:option" {...props}></Icon>
