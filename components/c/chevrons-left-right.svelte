<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0ipribch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0ipribch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chevrons-left-right" {...props}></Icon>
