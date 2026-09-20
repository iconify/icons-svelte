<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe80l4_cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xe80l4_cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:module-puzzle-1-solid" {...props}></Icon>
