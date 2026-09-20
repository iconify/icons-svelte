<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z47i7nbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z47i7nbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:getx" {...props}></Icon>
