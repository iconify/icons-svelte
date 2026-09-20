<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-h98du4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t-h98du4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-next-solid" {...props}></Icon>
