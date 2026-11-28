<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru4hu3bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru4hu3bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:key-round-check" {...props}></Icon>
