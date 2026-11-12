<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx8klrbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qx8klrbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librarything-light" {...props}></Icon>
