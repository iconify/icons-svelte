<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-3t8ob9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-3t8ob9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:fireball" {...props}></Icon>
