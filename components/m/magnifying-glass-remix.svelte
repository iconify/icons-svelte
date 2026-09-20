<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am86nkbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="am86nkbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:magnifying-glass-remix" {...props}></Icon>
