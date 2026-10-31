<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy610kn7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy610kn7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hand-grab-fill-round" {...props}></Icon>
