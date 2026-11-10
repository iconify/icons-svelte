<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of_zlmdfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="of_zlmdfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:haxe" {...props}></Icon>
