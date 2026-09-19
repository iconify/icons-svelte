<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjyf8l7ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjyf8l7ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:panorama-enlarge" {...props}></Icon>
