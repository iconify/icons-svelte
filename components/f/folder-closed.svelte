<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvjptdf5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="wvjptdf5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:folder-closed" {...props}></Icon>
