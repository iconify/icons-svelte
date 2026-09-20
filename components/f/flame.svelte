<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg4z99bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg4z99bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flame" {...props}></Icon>
