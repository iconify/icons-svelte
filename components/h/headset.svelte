<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3h22hb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="a3h22hb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:headset" {...props}></Icon>
