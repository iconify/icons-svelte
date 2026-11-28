<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfcoj9b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfcoj9b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bus-x" {...props}></Icon>
