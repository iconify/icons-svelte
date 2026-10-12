<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xphq9lb9l.css';
import '../../css/d/d32lng5vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xphq9lb9l"/><path class="d32lng5vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:exclamation-circle-stroke-20" {...props}></Icon>
