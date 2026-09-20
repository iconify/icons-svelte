<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui9v0tb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui9v0tb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flashlight-fill" {...props}></Icon>
