<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug1c8l74s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug1c8l74s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-z-hexagon-solid" {...props}></Icon>
