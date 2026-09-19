<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlkplcb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vlkplcb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:inspire-square" {...props}></Icon>
