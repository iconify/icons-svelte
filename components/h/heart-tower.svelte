<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g90x1bbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g90x1bbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-tower" {...props}></Icon>
