<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j155pvb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j155pvb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:memory-stick" {...props}></Icon>
