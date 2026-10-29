<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw6dpjb4k.css';
import '../../css/t/t-v91db8t.css';
import '../../css/g/glwfk_a6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw6dpjb4k wm-k"/><path class="t-v91db8t wm-s"/><path class="glwfk_a6x wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:remove-formatting" {...props}></Icon>
