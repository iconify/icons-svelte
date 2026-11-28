<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szr87acxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szr87acxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:corner-up-right" {...props}></Icon>
