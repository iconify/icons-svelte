<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrar2pyxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrar2pyxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:discord-fill-round" {...props}></Icon>
