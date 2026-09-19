<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy9s2_bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="vy9s2_bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brailleseven" {...props}></Icon>
