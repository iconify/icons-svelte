<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5eqpqbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="m5eqpqbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:i-cursor" {...props}></Icon>
