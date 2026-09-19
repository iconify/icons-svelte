<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt_n3ccpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lt_n3ccpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:level-up" {...props}></Icon>
