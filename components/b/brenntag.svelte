<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyuw9pk0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyuw9pk0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:brenntag" {...props}></Icon>
