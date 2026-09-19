<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0m3i396l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0m3i396l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pill" {...props}></Icon>
