<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybt0wbchx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybt0wbchx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-plus-duotone-round" {...props}></Icon>
