<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co7hbpbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co7hbpbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fish-audio" {...props}></Icon>
