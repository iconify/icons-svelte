<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btu6wmbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="btu6wmbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:protocols-square" {...props}></Icon>
