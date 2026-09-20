<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn419zgkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xn419zgkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsandbox-light" {...props}></Icon>
