<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aexv5vbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aexv5vbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hexagon-solid" {...props}></Icon>
