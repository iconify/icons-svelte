<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yau819bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yau819bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:grip" {...props}></Icon>
