<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps1-t3blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps1-t3blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:foodpanda" {...props}></Icon>
