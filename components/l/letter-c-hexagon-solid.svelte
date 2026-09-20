<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f38xf6bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f38xf6bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-c-hexagon-solid" {...props}></Icon>
