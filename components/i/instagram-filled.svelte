<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr2hhx8zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr2hhx8zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:instagram-filled" {...props}></Icon>
