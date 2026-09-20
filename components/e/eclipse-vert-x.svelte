<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydt4j0kfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydt4j0kfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eclipse-vert-x" {...props}></Icon>
