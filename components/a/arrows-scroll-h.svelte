<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6vlzc1us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6vlzc1us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrows-scroll-h" {...props}></Icon>
