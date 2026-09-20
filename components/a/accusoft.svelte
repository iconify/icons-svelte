<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5t-q7vil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5t-q7vil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:accusoft" {...props}></Icon>
