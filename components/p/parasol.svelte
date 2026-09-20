<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp2t3nbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp2t3nbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:parasol" {...props}></Icon>
