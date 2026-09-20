<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szb4ptbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="szb4ptbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:editimage" {...props}></Icon>
