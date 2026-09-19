<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l27e00btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="l27e00btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:closed-access-square" {...props}></Icon>
