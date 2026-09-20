<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfzsmob_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hfzsmob_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:expand-crop-resize-solid" {...props}></Icon>
