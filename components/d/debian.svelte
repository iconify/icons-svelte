<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbh-1ccij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbh-1ccij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:debian" {...props}></Icon>
