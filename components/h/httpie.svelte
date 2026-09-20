<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8x5s4moj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8x5s4moj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:httpie" {...props}></Icon>
