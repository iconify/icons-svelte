<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxonx6bxn.css';
import '../../css/g/gu-ybwb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxonx6bxn"/><path class="gu-ybwb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:rewind" {...props}></Icon>
