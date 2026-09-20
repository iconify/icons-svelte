<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4qr5-bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q4qr5-bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-favorite-solid" {...props}></Icon>
