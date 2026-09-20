<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/effjgp2eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="effjgp2eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:board-subway" {...props}></Icon>
