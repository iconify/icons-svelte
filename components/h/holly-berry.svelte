<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0611vbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0611vbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:holly-berry" {...props}></Icon>
