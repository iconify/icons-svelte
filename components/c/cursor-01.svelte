<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwiru2bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwiru2bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cursor-01" {...props}></Icon>
