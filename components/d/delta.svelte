<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d33quob0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d33quob0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:delta" {...props}></Icon>
