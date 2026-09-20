<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrd258wwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vrd258wwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dice5" {...props}></Icon>
