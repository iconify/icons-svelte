<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1lsc9bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1lsc9bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:arm-keil" {...props}></Icon>
