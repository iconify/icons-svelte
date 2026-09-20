<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvkcm2jga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":92.11};
const content = `<path class="bvkcm2jga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ngrok-dark" {...props}></Icon>
