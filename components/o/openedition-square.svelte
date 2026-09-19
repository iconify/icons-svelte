<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfkexgkrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kfkexgkrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:openedition-square" {...props}></Icon>
