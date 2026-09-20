<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqvc8qbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqvc8qbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opengl" {...props}></Icon>
