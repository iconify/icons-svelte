<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3v303tmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3v303tmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:caret-left" {...props}></Icon>
