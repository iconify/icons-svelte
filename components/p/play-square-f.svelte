<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd7ar58ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="nd7ar58ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:play-square-f" {...props}></Icon>
