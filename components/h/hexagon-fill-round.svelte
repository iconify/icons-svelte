<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt0hxmhgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt0hxmhgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-fill-round" {...props}></Icon>
