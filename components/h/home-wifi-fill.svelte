<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp4s1-v3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4s1-v3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-wifi-fill" {...props}></Icon>
