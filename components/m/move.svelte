<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcx6nf7bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-1};
const content = `<path class="wcx6nf7bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:move" {...props}></Icon>
