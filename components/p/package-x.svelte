<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1lne0b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1lne0b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:package-x" {...props}></Icon>
