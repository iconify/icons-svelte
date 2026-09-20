<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axx3xybtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axx3xybtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:joplin" {...props}></Icon>
