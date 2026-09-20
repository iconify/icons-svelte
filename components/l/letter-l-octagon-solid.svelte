<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an3y2z25r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an3y2z25r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-l-octagon-solid" {...props}></Icon>
