<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4t6tyb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4t6tyb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clock-pause" {...props}></Icon>
