<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9adr-b_h.css';
import '../../css/d/d7q3yfbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9adr-b_h"/><path class="d7q3yfbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:call-incoming-filled" {...props}></Icon>
