<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy1dny6wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="cy1dny6wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:paperclip" {...props}></Icon>
