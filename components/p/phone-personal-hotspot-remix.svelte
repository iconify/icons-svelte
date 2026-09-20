<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipukzek5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipukzek5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-personal-hotspot-remix" {...props}></Icon>
