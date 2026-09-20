<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-dv1svnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d-dv1svnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:orientation-portrait-solid" {...props}></Icon>
