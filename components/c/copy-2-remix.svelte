<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9_cz0n8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z9_cz0n8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:copy-2-remix" {...props}></Icon>
