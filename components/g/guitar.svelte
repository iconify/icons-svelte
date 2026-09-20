<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sio_2yb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="sio_2yb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:guitar" {...props}></Icon>
