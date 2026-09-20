<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jye8v80ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jye8v80ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ford-light" {...props}></Icon>
