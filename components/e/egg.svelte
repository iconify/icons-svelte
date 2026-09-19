<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgg3rfb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mgg3rfb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:egg" {...props}></Icon>
