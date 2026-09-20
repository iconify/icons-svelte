<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smezn0u9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="smezn0u9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:justice-hammer-remix" {...props}></Icon>
