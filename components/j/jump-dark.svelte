<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9j50ebdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9j50ebdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jump-dark" {...props}></Icon>
