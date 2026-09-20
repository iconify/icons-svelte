<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiiiy52kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiiiy52kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:librariesdotio" {...props}></Icon>
