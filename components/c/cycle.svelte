<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3nr2d6ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3nr2d6ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cycle" {...props}></Icon>
