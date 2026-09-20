<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc20habja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc20habja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrowhead-down" {...props}></Icon>
