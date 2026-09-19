<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hro-8ebhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hro-8ebhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:emoji-really" {...props}></Icon>
