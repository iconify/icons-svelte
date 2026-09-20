<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo82rsbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo82rsbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bombardier" {...props}></Icon>
