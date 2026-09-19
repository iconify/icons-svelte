<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haaod9unz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="haaod9unz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-7-diamonds" {...props}></Icon>
