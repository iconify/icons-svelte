<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp570eboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp570eboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:karate" {...props}></Icon>
