<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxqulz4gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxqulz4gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-beautify" {...props}></Icon>
