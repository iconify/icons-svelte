<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxkzqccrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxkzqccrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:module-puzzle-2" {...props}></Icon>
