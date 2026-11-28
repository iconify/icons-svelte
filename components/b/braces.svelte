<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avc2a9nxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avc2a9nxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:braces" {...props}></Icon>
