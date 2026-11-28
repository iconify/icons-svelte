<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vunnzhbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vunnzhbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hand-heart" {...props}></Icon>
