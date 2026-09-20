<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxhcf7bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxhcf7bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:fullscreen-exit" {...props}></Icon>
