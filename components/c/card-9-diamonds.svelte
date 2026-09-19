<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y05w8bbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y05w8bbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-9-diamonds" {...props}></Icon>
