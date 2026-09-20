<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwqo_9cnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mwqo_9cnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:christian-cross-2" {...props}></Icon>
