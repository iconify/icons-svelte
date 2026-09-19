<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4cztab1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4cztab1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:corner-top-left" {...props}></Icon>
