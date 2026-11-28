<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t88qepbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t88qepbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-pin-solid" {...props}></Icon>
