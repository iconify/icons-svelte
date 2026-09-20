<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfb41c2xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfb41c2xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:camunda" {...props}></Icon>
