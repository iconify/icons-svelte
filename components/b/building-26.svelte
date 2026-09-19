<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_x215gla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="t_x215gla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:building-26" {...props}></Icon>
