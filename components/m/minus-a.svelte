<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru1vegbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru1vegbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:minus-a" {...props}></Icon>
