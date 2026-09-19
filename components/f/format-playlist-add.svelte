<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3p5n_b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="f3p5n_b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-playlist-add" {...props}></Icon>
