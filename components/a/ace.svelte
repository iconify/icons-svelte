<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6vqi3zez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6vqi3zez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ace" {...props}></Icon>
