<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr-5uqbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="jr-5uqbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-right-arrow-left" {...props}></Icon>
