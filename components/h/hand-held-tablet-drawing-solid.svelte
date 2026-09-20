<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9r6-7chp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s9r6-7chp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hand-held-tablet-drawing-solid" {...props}></Icon>
