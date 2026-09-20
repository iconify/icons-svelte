<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unm720e2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="unm720e2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:locked-lock-with-keyhole" {...props}></Icon>
