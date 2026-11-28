<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyeje6p9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyeje6p9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mushroom-solid" {...props}></Icon>
