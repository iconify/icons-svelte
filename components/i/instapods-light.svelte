<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk1zdgbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sk1zdgbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instapods-light" {...props}></Icon>
