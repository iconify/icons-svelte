<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uti1qabby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uti1qabby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gift-remix" {...props}></Icon>
