<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhfzzxb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uhfzzxb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:google-with-circle" {...props}></Icon>
