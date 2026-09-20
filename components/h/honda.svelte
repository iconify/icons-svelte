<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yje1y7w0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yje1y7w0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:honda" {...props}></Icon>
