<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s833exkju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="s833exkju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:mendeley-square" {...props}></Icon>
