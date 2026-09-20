<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0mnjlb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x0mnjlb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postiz-dark" {...props}></Icon>
