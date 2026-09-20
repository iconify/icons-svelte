<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c71wkui3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c71wkui3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:redbubble" {...props}></Icon>
