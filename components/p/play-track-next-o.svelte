<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoey5m-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zoey5m-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-track-next-o" {...props}></Icon>
