<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dep2gs26u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dep2gs26u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:arrow-big-up" {...props}></Icon>
