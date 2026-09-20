<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thwwwfbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thwwwfbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-square" {...props}></Icon>
