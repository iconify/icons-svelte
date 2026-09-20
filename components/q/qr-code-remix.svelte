<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu_n6gdgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hu_n6gdgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:qr-code-remix" {...props}></Icon>
