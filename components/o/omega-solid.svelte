<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpu8p3bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpu8p3bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:omega-solid" {...props}></Icon>
